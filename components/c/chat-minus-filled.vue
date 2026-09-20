<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xflx9c36z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xflx9c36z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-minus-filled" /></template>
