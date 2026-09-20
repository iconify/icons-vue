<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0ibg0ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d0ibg0ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-shrink-diagonal-2-solid" /></template>
