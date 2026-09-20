<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4f8fb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu4f8fb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:account-pin-circle-line" /></template>
