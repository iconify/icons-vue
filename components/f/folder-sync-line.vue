<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjl68_bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjl68_bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-sync-line" /></template>
