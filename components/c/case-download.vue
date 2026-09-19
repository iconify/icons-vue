<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw3vozd0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":416};
const content = `<path class="qw3vozd0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:case-download" /></template>
