<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldnl1xm9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldnl1xm9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:end-point-circle-bold" /></template>
