<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctt6wubfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctt6wubfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:etsy" /></template>
