<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqc81jp9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqc81jp9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ant" /></template>
