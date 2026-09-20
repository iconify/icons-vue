<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q80p7-jst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q80p7-jst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:customer-support-1-remix" /></template>
