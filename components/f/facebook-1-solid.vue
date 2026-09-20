<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re4fspsiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="re4fspsiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:facebook-1-solid" /></template>
