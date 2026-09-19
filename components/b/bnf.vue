<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx226zbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mx226zbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:bnf" /></template>
