<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i70hjbphk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i70hjbphk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-stamp-mail" /></template>
