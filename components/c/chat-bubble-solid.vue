<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_2501bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_2501bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-solid" /></template>
