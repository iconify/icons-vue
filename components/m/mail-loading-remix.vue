<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_982bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in_982bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:mail-loading-remix" /></template>
