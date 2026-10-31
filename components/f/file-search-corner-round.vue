<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfq142g3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfq142g3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-search-corner-round" /></template>
