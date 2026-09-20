<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy6d1wrkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy6d1wrkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-3-fill" /></template>
