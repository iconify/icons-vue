<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clluj0x1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clluj0x1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-1-fill" /></template>
