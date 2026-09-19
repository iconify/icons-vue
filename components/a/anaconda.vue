<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo27_sxlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yo27_sxlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:anaconda" /></template>
