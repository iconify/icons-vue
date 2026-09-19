<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llpghbi5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="llpghbi5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:caret-top" /></template>
