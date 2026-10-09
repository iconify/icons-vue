<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iij7ri-7j.css';
import '../../css/k/k_0c2xn7m.css';
import '../../css/s/st8n3_8ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iij7ri-7j"/><path class="k_0c2xn7m"/><path class="st8n3_8ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:airport-48" /></template>
