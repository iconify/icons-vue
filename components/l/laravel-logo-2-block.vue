<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffedq_qna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffedq_qna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:laravel-logo-2-block" /></template>
