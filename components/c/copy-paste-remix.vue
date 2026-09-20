<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vleejw2oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vleejw2oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:copy-paste-remix" /></template>
