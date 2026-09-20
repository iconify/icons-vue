<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj3g5vbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hj3g5vbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:feed" /></template>
