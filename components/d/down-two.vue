<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrng66bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yrng66bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:down-two" /></template>
