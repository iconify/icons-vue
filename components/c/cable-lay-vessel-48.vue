<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4m--tbpp.css';
import '../../css/i/ijgbmtb8w.css';
import '../../css/f/fiqktq5gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v4m--tbpp"/><path class="ijgbmtb8w"/><path class="fiqktq5gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lay-vessel-48" /></template>
