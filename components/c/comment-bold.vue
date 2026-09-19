<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdjivdz5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdjivdz5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-bold" /></template>
