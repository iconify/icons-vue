<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swgsnbfka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swgsnbfka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-down-48" /></template>
