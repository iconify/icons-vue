<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z25xg7b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z25xg7b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chess-bishop" /></template>
