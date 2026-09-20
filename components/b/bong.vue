<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u562g2b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u562g2b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bong" /></template>
