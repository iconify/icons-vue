<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfq4xub6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfq4xub6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-circle-text-filled" /></template>
