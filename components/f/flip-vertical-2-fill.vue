<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvooqgs_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvooqgs_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flip-vertical-2-fill" /></template>
