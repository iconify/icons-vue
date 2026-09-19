<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc-276b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc-276b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layers-plus" /></template>
