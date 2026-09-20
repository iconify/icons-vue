<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfa599b0o.css';
import '../../css/p/pc_zkzb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfa599b0o"/><path class="pc_zkzb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bilibili-logo-bold" /></template>
