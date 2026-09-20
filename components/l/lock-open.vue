<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqw9hh_pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqw9hh_pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:lock-open" /></template>
