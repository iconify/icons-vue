<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcv261bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcv261bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubble-chat-temporary" /></template>
