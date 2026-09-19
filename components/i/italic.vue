<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub6_l5tno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ub6_l5tno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:italic" /></template>
