<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb9uslyzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mb9uslyzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kali-linux" /></template>
