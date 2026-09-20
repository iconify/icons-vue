<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tunre70_k.css';
import '../../css/f/f_afl5b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tunre70_k"/><path class="f_afl5b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-tray" /></template>
