<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6fl38b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6fl38b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:laugh-gloss" /></template>
