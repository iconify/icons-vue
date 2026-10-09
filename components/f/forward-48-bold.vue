<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_i86cclf.css';
import '../../css/a/an8j9_bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h_i86cclf"/><path class="an8j9_bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forward-48-bold" /></template>
