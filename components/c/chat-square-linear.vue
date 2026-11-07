<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llj5-713t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llj5-713t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-linear" /></template>
