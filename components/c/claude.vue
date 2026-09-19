<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws87yvbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ws87yvbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:claude" /></template>
