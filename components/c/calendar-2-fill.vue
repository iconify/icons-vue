<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qprw-3b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qprw-3b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-2-fill" /></template>
