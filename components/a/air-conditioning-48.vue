<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3-w5po8z.css';
import '../../css/k/kyspg4brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3-w5po8z"/><path class="kyspg4brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:air-conditioning-48" /></template>
