<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd80xzbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd80xzbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:autodesk-revit" /></template>
