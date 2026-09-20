<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3js_p-8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3js_p-8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-docs" /></template>
