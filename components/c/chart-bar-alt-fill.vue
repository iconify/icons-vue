<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtm3r7b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rtm3r7b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-bar-alt-fill" /></template>
