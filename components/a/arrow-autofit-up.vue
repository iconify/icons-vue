<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7ld7wu0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ld7wu0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-autofit-up" /></template>
