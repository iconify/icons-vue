<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkr13bxin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkr13bxin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:backward-circle" /></template>
