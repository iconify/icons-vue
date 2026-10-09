<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8_-mvbmk.css';
import '../../css/n/n5nqfww4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x8_-mvbmk"/><path class="n5nqfww4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-to-line-48-bold" /></template>
