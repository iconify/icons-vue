<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzysto7mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xzysto7mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:health-care-2-remix" /></template>
