<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3u88lbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3u88lbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-v-filled" /></template>
