<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh9nduq0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qh9nduq0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:ice-tea" /></template>
