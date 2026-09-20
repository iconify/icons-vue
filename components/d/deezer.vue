<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okvyj4bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okvyj4bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deezer" /></template>
