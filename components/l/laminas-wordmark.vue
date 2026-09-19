<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6fxsjc6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="y6fxsjc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:laminas-wordmark" /></template>
