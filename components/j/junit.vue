<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drn_i5bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="drn_i5bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:junit" /></template>
