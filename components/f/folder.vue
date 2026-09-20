<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thdeo9zrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thdeo9zrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:folder" /></template>
