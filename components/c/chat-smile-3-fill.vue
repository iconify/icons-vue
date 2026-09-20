<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvgsdedrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvgsdedrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-3-fill" /></template>
