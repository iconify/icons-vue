<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg1yy-brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg1yy-brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cake-star" /></template>
