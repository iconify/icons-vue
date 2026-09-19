<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrrvbnmng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrrvbnmng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-diagonal" /></template>
