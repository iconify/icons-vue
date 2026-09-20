<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-l9phbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y-l9phbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chat-16" /></template>
