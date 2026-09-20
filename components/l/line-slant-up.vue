<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebzo_ioua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ebzo_ioua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:line-slant-up" /></template>
