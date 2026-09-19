<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv-xs0bgz.css';
import '../../css/h/h8m5eji-v.css';
import '../../css/g/g5ov6kbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tv-xs0bgz"/><path class="h8m5eji-v"/><path class="g5ov6kbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:leaffluttering" /></template>
