<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko0w27bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko0w27bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-plus" /></template>
