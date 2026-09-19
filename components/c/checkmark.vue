<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hocb8ccfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hocb8ccfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:checkmark" /></template>
