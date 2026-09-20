<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjqu2ujmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gjqu2ujmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-video-bold" /></template>
