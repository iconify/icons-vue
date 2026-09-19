<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6la5eb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6la5eb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:api" /></template>
