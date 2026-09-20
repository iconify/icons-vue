<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7xu3gy5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7xu3gy5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-rotary-first-right" /></template>
