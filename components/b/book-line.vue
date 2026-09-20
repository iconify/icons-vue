<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xejf3lboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xejf3lboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:book-line" /></template>
