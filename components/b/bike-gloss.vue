<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qitgpr0fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qitgpr0fk wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bike-gloss" /></template>
