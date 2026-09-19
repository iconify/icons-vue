<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo7aoqzxk.css';
import '../../css/l/l4be4thee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jo7aoqzxk"/><path class="l4be4thee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-email" /></template>
