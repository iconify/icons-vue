<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7ou1kbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d7ou1kbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:machine-b" /></template>
