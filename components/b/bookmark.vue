<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcv-msb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rcv-msb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:bookmark" /></template>
