<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofzqahbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ofzqahbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chat-26" /></template>
