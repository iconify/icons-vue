<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi856n_4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wi856n_4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:left-one" /></template>
