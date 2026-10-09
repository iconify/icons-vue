<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdt97jb-t.css';
import '../../css/x/xj1iovt4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zdt97jb-t"/><path class="xj1iovt4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-up-48" /></template>
