<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4h395b6q.css';
import '../../css/w/w4luyebbu.css';
import '../../css/e/eun9ccb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4h395b6q"/><path class="w4luyebbu"/><path class="eun9ccb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:email-mailbox-open" /></template>
