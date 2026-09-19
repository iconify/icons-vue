<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3_j8y16n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3_j8y16n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:horizontal-tidy-up" /></template>
