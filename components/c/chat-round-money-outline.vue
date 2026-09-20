<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyh_xgu6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fyh_xgu6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-money-outline" /></template>
