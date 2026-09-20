<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqh4zbbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqh4zbbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:color-picker-2" /></template>
