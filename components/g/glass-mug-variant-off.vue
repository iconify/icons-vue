<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq2872btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq2872btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glass-mug-variant-off" /></template>
