<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7i92f-yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7i92f-yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:five-star-badge" /></template>
