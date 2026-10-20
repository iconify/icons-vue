<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyn89ysya.css';
import '../../css/u/usuy8n_ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uyn89ysya"/><path class="usuy8n_ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-top-20" /></template>
