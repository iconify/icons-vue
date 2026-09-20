<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_6ul21wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_6ul21wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-linear" /></template>
