<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqwrgzbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":737,"height":646};
const content = `<path class="wqwrgzbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:camera" /></template>
