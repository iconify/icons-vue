<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa--x8bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qa--x8bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:light" /></template>
