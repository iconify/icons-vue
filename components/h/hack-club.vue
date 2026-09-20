<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhke2_bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhke2_bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hack-club" /></template>
