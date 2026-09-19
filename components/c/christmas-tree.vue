<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4s0l0b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s4s0l0b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:christmas-tree" /></template>
