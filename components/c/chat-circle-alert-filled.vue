<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vysr3ibfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vysr3ibfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-alert-filled" /></template>
