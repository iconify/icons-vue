<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npjkx-b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npjkx-b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-plus-bold" /></template>
