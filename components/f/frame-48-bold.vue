<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klcw8eg5x.css';
import '../../css/s/s55bi35kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="klcw8eg5x"/><path class="s55bi35kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frame-48-bold" /></template>
