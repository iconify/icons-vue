<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f32zxbc_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f32zxbc_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-5-line" /></template>
