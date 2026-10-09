<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9l2qqe6j.css';
import '../../css/b/bkiex1byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9l2qqe6j"/><path class="bkiex1byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-bar-48" /></template>
