<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arrq9cbru.css';
import '../../css/d/d08_cxnnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="arrq9cbru"/><path class="d08_cxnnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:javascript" /></template>
