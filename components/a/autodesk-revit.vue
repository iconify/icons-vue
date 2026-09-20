<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf1i8ngqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf1i8ngqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:autodesk-revit" /></template>
