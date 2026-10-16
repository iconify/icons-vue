<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7tl1ob_w.css';
import '../../css/g/gdz_w_6os.css';
import '../../css/c/c65-ehvfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7tl1ob_w"/><path class="gdz_w_6os"/><path class="c65-ehvfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-sphere-48" /></template>
