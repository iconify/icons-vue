<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjku7rbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjku7rbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bluetooth-searching" /></template>
