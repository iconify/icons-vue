<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j92jj3b8h.css';
import '../../css/w/wh8ezzf6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="j92jj3b8h"/><path class="wh8ezzf6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:albums-outline" /></template>
