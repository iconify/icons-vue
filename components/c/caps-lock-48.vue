<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv1mbkbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hv1mbkbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caps-lock-48" /></template>
