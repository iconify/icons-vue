<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9_0x6oon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9_0x6oon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-alt-x" /></template>
