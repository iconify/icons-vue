<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl4mpkbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xl4mpkbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-pdf" /></template>
