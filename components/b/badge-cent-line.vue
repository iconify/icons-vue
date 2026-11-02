<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6c8e7biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6c8e7biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-cent-line" /></template>
