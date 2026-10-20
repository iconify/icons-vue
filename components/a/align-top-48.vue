<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjtwhsb_o.css';
import '../../css/x/xg42qpbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fjtwhsb_o"/><path class="xg42qpbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-top-48" /></template>
