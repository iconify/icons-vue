<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhc1gwbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhc1gwbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:emoji-sad" /></template>
