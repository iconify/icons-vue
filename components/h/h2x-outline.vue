<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoip6sbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yoip6sbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:h2x-outline" /></template>
