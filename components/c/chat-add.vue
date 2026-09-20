<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ottw1fb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ottw1fb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:chat-add" /></template>
