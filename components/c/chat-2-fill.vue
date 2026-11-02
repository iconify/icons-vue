<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q75iphppk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q75iphppk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-2-fill" /></template>
