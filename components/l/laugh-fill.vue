<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-6vsyqaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-6vsyqaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:laugh-fill" /></template>
