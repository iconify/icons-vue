<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkg5m648j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkg5m648j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chat-conversation" /></template>
