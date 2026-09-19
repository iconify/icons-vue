<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofaga73oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ofaga73oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:chat-round" /></template>
