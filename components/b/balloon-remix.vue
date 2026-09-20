<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmk1fbcho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zmk1fbcho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:balloon-remix" /></template>
