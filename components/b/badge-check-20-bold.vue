<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-q-p1bwi.css';
import '../../css/t/tld7w6b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m-q-p1bwi"/><path class="tld7w6b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-check-20-bold" /></template>
