<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioepsabuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ioepsabuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:eraser-20-solid" /></template>
