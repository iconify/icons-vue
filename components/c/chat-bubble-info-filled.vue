<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clvq9sbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clvq9sbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble-info-filled" /></template>
