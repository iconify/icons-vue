<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yexb5pbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yexb5pbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:format-horizontal-align-center" /></template>
