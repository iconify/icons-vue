<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twmqo33gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="twmqo33gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ladder-water" /></template>
