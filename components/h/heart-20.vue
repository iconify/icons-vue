<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kob_3fbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kob_3fbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-20" /></template>
