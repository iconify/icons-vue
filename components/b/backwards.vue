<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgnj9kbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xgnj9kbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:backwards" /></template>
