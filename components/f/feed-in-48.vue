<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/friknfboq.css';
import '../../css/v/v3-yombvq.css';
import '../../css/v/v403anbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="friknfboq"/><path class="v3-yombvq"/><path class="v403anbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:feed-in-48" /></template>
