<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvvf71v4s.css';
import '../../css/k/krurd6_gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvvf71v4s"/><path class="krurd6_gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flow-battery-48" /></template>
