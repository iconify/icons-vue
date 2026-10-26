<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlnwz7iwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":303,"height":303};
const content = `<path class="zlnwz7iwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apollodotio" /></template>
