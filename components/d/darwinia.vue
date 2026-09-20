<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1fzc2bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1fzc2bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:darwinia" /></template>
