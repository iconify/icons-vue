<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go8sgfrep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go8sgfrep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-solid" /></template>
