<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sreo9ebug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sreo9ebug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-check-filled" /></template>
