<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv1yczbez.css';
import '../../css/e/enk161xfw.css';
import '../../css/t/trgl4klpj.css';
import '../../css/a/aj84m6bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gv1yczbez"/><path class="enk161xfw"/><path class="trgl4klpj"/><path class="aj84m6bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gazebo" /></template>
