<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8jsxg0hb.css';
import '../../css/y/y288-qr4x.css';
import '../../css/z/zzhfcob3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8jsxg0hb"/><path class="y288-qr4x"/><path class="zzhfcob3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-search-48-bold" /></template>
