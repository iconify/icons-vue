<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dom1d86ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dom1d86ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-linear" /></template>
