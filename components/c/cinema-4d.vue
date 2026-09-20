<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq23ysbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq23ysbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cinema-4d" /></template>
