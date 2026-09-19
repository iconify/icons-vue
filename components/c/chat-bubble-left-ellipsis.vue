<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk7h7zblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7h7zblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat-bubble-left-ellipsis" /></template>
