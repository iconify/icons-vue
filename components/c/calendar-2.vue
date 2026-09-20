<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kumxoab-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kumxoab-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:calendar-2" /></template>
