<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqs9nibzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqs9nibzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:information-off-fill" /></template>
