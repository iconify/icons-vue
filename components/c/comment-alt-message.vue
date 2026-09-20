<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyvx3ccox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyvx3ccox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-message" /></template>
