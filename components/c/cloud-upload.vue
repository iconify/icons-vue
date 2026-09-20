<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko8ntx8ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko8ntx8ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-upload" /></template>
