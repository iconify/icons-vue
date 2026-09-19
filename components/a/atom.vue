<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfw7oseas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="yfw7oseas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:atom" /></template>
