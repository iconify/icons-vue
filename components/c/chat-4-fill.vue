<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr_a0tb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr_a0tb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-4-fill" /></template>
