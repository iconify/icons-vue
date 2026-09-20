<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyhk6-brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xyhk6-brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:align-right-1-remix" /></template>
