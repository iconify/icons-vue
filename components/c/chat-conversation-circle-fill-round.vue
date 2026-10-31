<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3za1pbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3za1pbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-circle-fill-round" /></template>
