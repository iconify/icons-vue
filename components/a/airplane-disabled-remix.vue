<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak_q72b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ak_q72b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:airplane-disabled-remix" /></template>
