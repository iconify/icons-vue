<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxi53eduq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxi53eduq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-filled" /></template>
