<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev91xjb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev91xjb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat-bubble-oval-left" /></template>
