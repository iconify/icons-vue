<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylsm6d0zn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ylsm6d0zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-line" /></template>
