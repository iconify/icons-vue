<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgy1l_tlx.css';
import '../../css/i/icm3m1b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hgy1l_tlx"/><path class="icm3m1b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-20-bold" /></template>
