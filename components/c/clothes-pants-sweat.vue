<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz8-vsbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sz8-vsbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:clothes-pants-sweat" /></template>
