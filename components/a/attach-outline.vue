<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzaaavbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzaaavbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:attach-outline" /></template>
