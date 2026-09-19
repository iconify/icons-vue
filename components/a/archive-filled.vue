<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl_7r6bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl_7r6bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:archive-filled" /></template>
