<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1p_6uu5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1p_6uu5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:back2-filled" /></template>
