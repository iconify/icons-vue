<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2cojm2_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v2cojm2_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-refresh-remix" /></template>
