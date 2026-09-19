<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm8gc9syk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm8gc9syk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat-bubble" /></template>
