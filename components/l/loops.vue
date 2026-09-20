<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxsg9ybrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxsg9ybrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:loops" /></template>
