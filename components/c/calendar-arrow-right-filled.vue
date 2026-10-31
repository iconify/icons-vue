<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9svjjhpo.css';
import '../../css/v/v1_dsqc1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9svjjhpo"/><path class="v1_dsqc1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-arrow-right-filled" /></template>
