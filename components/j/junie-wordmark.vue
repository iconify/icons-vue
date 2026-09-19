<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb3137b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zb3137b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:junie-wordmark" /></template>
