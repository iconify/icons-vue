<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4u8blsoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4u8blsoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-annotation-plus" /></template>
