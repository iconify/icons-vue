<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdh48zxjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gdh48zxjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:brightness-3" /></template>
