<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzoi8ll2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kzoi8ll2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bow" /></template>
