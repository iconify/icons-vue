<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj614lbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bj614lbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hierarchy-1" /></template>
