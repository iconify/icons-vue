<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2_wh8b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2_wh8b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:litiengine" /></template>
