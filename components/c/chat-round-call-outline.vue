<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s42gq2v8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s42gq2v8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-call-outline" /></template>
