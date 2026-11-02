<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dad9wjbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dad9wjbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-3-fill" /></template>
