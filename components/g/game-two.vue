<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmf0e302q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zmf0e302q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:game-two" /></template>
