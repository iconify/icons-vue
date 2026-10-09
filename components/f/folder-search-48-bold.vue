<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx3v-fbjr.css';
import '../../css/v/v3vwc3z2u.css';
import '../../css/z/zzhfcob3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hx3v-fbjr"/><path class="v3vwc3z2u"/><path class="zzhfcob3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-search-48-bold" /></template>
