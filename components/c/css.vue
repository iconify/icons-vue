<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd3-ei29r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dd3-ei29r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:css" /></template>
