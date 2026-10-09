<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g81g92bif.css';
import '../../css/w/wrr9qib1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g81g92bif"/><path class="wrr9qib1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charity-48" /></template>
