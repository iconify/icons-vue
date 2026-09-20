<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvzh4z13o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvzh4z13o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-chat-logo-block" /></template>
