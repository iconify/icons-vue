<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb-1k-83z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb-1k-83z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:app-window-refresh" /></template>
