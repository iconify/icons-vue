<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-csnccpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-csnccpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-2-fill" /></template>
