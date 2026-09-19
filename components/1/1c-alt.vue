<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsak5lzio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wsak5lzio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:1c-alt" /></template>
