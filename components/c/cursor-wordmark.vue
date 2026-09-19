<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyb0hxdvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wyb0hxdvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cursor-wordmark" /></template>
