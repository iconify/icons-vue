<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeo-4db_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeo-4db_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-vertical-fill" /></template>
