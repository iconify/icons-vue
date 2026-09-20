<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu5306mfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bu5306mfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-call-bold" /></template>
