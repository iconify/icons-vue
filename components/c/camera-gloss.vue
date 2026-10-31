<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obiis19rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obiis19rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:camera-gloss" /></template>
