<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr3r60b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sr3r60b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chess-king-solid" /></template>
