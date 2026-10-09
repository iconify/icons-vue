<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egi8qzduf.css';
import '../../css/t/tly4pwr5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="egi8qzduf"/><path class="tly4pwr5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-tub-48" /></template>
