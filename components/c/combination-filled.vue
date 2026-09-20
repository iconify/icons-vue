<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8iykhp2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8iykhp2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:combination-filled" /></template>
