<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwkjjbb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wwkjjbb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-gaming-1-solid" /></template>
