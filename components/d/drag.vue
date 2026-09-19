<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpamcyuwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lpamcyuwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:drag" /></template>
