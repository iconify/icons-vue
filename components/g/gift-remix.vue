<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uti1qabby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uti1qabby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:gift-remix" /></template>
