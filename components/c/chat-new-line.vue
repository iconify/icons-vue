<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3pvbvbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3pvbvbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-new-line" /></template>
