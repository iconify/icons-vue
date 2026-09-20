<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_a6-pb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_a6-pb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:aspect-ratio-line" /></template>
