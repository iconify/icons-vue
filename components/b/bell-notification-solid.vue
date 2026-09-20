<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6wm8ehfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d6wm8ehfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bell-notification-solid" /></template>
