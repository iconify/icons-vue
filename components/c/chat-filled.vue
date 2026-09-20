<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt41hsqgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt41hsqgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-filled" /></template>
