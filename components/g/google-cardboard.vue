<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6vo_obpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6vo_obpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-cardboard" /></template>
