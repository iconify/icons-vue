<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho99joejz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho99joejz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kedro" /></template>
