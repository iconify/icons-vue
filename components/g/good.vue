<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2w8nrbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y2w8nrbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:good" /></template>
