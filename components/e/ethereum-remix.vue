<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfvd3kb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hfvd3kb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ethereum-remix" /></template>
