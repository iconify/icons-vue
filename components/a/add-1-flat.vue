<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs903ixzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gs903ixzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:add-1-flat" /></template>
