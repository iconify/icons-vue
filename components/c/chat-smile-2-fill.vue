<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f664y_bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f664y_bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-2-fill" /></template>
