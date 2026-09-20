<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyvtfptam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyvtfptam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-search" /></template>
