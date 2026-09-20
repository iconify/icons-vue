<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkhwucc5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkhwucc5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chat-question-24" /></template>
