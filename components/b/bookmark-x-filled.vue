<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4-1nacqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t4-1nacqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bookmark-x-filled" /></template>
