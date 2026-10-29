<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0yoxtbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0yoxtbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-down" /></template>
