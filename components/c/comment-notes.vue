<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w53kg79zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w53kg79zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-notes" /></template>
