<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek-30ob9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek-30ob9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:close2-outlined" /></template>
