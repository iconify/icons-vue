<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik1_o3bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":384};
const content = `<path class="ik1_o3bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mail-reply-all" /></template>
