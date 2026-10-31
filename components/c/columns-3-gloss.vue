<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmlu_gbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmlu_gbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:columns-3-gloss" /></template>
