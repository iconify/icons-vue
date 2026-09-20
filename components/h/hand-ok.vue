<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb65a0hev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hb65a0hev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-ok" /></template>
