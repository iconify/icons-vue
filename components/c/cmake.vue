<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abw90sbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="abw90sbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cmake" /></template>
