<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll58u1lzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll58u1lzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrows-up-from-line" /></template>
