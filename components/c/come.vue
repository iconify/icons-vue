<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u218tr9hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u218tr9hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:come" /></template>
