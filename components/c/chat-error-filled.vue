<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n885a6bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n885a6bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-error-filled" /></template>
