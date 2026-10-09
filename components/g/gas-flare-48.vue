<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkkf-abgy.css';
import '../../css/e/e73jcmbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkkf-abgy"/><path class="e73jcmbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-flare-48" /></template>
