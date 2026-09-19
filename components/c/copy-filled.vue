<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3mrqjpwv.css';
import '../../css/y/yft_2jb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="i3mrqjpwv"/><path class="yft_2jb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:copy-filled" /></template>
