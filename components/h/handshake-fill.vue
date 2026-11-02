<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3u1jcbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3u1jcbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:handshake-fill" /></template>
