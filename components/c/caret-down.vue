<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfximt3op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1280};
const content = `<path class="pfximt3op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:caret-down" /></template>
