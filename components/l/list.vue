<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3decsfqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f3decsfqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:list" /></template>
