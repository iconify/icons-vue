<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbwxlclgf.css';
import '../../css/u/u5hq78bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lbwxlclgf"/><path class="u5hq78bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charge-point-sign-48" /></template>
