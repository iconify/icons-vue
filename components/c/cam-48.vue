<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl-yfkvrr.css';
import '../../css/p/p7gth1bju.css';
import '../../css/b/bujm-4v9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pl-yfkvrr"/><path class="p7gth1bju"/><path class="bujm-4v9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cam-48" /></template>
