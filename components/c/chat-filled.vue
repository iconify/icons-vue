<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp254zi-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bp254zi-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-filled" /></template>
