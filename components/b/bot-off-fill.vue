<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r59-vnb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r59-vnb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bot-off-fill" /></template>
