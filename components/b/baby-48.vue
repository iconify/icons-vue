<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7474gbcq.css';
import '../../css/w/w2h_ynbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w7474gbcq"/><path class="w2h_ynbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:baby-48" /></template>
