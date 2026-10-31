<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojkk-2kby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojkk-2kby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-fill-round" /></template>
