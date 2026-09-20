<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq3t-owyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zq3t-owyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:border-bottom-solid" /></template>
