<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqov3yajq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wqov3yajq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:auto-width" /></template>
