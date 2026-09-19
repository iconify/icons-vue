<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj0su9btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj0su9btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-left" /></template>
