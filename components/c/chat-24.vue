<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9wyzcc1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9wyzcc1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chat-24" /></template>
