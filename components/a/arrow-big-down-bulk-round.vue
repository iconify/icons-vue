<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv93zobeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv93zobeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-down-bulk-round" /></template>
