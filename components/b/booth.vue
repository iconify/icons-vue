<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3zcx14y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pc3zcx14y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:booth" /></template>
