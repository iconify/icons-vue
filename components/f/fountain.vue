<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezpc1_buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ezpc1_buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fountain" /></template>
