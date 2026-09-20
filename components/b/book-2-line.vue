<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn55p_bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn55p_bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:book-2-line" /></template>
