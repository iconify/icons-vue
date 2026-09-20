<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndlt7bcrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndlt7bcrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-outline" /></template>
