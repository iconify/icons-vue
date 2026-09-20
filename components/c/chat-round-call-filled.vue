<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqyvaqixp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uqyvaqixp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-call-filled" /></template>
