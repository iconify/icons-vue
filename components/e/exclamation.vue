<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vad9-vkwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vad9-vkwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:exclamation" /></template>
