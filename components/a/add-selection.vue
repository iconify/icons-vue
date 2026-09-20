<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv7k113ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mv7k113ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-selection" /></template>
