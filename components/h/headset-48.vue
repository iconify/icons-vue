<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm-p03j5f.css';
import '../../css/k/k57qbuvoz.css';
import '../../css/b/bwg7bobur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pm-p03j5f"/><path class="k57qbuvoz"/><path class="bwg7bobur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:headset-48" /></template>
