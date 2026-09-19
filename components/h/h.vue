<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzeyg_bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzeyg_bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:h" /></template>
