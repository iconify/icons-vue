<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2ru3b4ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2ru3b4ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:commodore" /></template>
