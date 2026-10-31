<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6z27mruz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6z27mruz wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-open-gloss" /></template>
