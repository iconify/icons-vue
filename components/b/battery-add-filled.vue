<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy9twf5me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy9twf5me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:battery-add-filled" /></template>
