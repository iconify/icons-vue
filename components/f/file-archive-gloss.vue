<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkvl1_a7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkvl1_a7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-archive-gloss" /></template>
