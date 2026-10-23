<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb_4qqbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb_4qqbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bookmark-plus" /></template>
