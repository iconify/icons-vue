<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9itrbcfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y9itrbcfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:co2-48" /></template>
