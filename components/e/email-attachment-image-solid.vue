<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8ll5jb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8ll5jb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:email-attachment-image-solid" /></template>
