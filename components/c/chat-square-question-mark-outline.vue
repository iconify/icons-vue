<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czn8j8ltd.css';
import '../../css/j/jp3kqwdgu.css';
import '../../css/u/um_zvyb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czn8j8ltd"/><path class="jp3kqwdgu"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-question-mark-outline" /></template>
