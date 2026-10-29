<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zduqu9ruz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zduqu9ruz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-down" /></template>
