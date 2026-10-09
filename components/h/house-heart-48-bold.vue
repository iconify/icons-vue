<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfpjugbvy.css';
import '../../css/t/tqb1tpb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="tqb1tpb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-heart-48-bold" /></template>
