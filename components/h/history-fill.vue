<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6wlbubwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6wlbubwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:history-fill" /></template>
