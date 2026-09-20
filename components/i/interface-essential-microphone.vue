<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0isofspd.css';
import '../../css/u/usr-jnz4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0isofspd"/><path class="usr-jnz4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-microphone" /></template>
