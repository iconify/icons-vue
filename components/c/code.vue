<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbtlko4kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbtlko4kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:code" /></template>
