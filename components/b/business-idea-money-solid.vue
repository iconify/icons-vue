<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtief1bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qtief1bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:business-idea-money-solid" /></template>
