<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lythdhbow.css';
import '../../css/f/f4kf9cc7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lythdhbow"/><path class="f4kf9cc7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:chat-dot-square" /></template>
