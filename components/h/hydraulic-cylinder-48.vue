<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9og61b7p.css';
import '../../css/y/yftb-1bif.css';
import '../../css/p/pzgm9abmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9og61b7p"/><path class="yftb-1bif"/><path class="pzgm9abmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydraulic-cylinder-48" /></template>
