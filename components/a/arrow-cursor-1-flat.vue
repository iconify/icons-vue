<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji-te0b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ji-te0b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:arrow-cursor-1-flat" /></template>
