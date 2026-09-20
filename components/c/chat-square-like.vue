<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j64rr6bcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j64rr6bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-square-like" /></template>
