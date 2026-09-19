<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvbk_blhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="mvbk_blhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:astro" /></template>
