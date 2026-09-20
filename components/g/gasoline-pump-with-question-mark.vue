<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srr1b7b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="srr1b7b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gasoline-pump-with-question-mark" /></template>
