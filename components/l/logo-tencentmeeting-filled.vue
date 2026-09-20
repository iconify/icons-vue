<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nffkq2bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nffkq2bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-tencentmeeting-filled" /></template>
