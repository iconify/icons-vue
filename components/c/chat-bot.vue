<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmul-cc-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pmul-cc-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chat-bot" /></template>
