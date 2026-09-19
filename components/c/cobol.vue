<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li61mcc3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="li61mcc3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cobol" /></template>
