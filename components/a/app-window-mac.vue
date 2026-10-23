<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/serxxpm-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="serxxpm-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:app-window-mac" /></template>
