<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap42-obbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ap42-obbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:horizontal-menu-circle-remix" /></template>
