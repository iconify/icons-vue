<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ibjvb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t5ibjvb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fit-to-height-square-solid" /></template>
