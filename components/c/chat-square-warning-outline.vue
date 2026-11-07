<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czn8j8ltd.css';
import '../../css/g/ga24sqbtj.css';
import '../../css/u/um_zvyb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czn8j8ltd"/><path class="ga24sqbtj"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-warning-outline" /></template>
