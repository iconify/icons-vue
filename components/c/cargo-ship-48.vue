<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw0_76buw.css';
import '../../css/d/d22vebp3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cw0_76buw"/><path class="d22vebp3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cargo-ship-48" /></template>
