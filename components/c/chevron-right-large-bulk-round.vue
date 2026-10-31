<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0a7fgn5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0a7fgn5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-right-large-bulk-round" /></template>
