<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovtdw1bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ovtdw1bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-rating-48-bold" /></template>
