<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfipc4_ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfipc4_ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:category-outline" /></template>
