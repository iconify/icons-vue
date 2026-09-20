<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg38sdwxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg38sdwxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comment-2-text" /></template>
