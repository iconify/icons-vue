<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p56rd3bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p56rd3bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:comment-dots-filled" /></template>
