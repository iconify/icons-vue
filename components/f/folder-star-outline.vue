<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl-3rkfbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl-3rkfbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-star-outline" /></template>
