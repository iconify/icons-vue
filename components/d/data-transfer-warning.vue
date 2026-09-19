<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epmzw59au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epmzw59au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:data-transfer-warning" /></template>
