<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq-76r4lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-76r4lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-key-fill" /></template>
