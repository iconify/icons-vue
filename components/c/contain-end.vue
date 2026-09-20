<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op7cm53as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op7cm53as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:contain-end" /></template>
