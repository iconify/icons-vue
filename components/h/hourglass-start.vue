<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6l6uacfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="p6l6uacfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hourglass-start" /></template>
