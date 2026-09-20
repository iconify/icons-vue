<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tifla0bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tifla0bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-dots-filled" /></template>
