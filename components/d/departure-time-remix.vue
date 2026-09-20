<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr2e7hb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jr2e7hb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:departure-time-remix" /></template>
