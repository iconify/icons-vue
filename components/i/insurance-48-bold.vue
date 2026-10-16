<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc46o1p0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xc46o1p0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:insurance-48-bold" /></template>
