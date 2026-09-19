<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngmmfbbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="ngmmfbbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-underlined" /></template>
