<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylkfh-8lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylkfh-8lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:handshake-line" /></template>
