<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x62avfvkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x62avfvkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:fan" /></template>
