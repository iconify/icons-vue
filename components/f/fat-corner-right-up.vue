<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j096u3bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j096u3bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-right-up" /></template>
