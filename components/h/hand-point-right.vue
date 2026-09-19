<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0n0-5b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i0n0-5b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hand-point-right" /></template>
