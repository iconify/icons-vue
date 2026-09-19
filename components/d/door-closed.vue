<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5ya-xbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g5ya-xbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:door-closed" /></template>
