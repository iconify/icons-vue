<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7_cf1b6s.css';
import '../../css/l/liguc8hzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i7_cf1b6s"/><path class="liguc8hzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-off-48" /></template>
