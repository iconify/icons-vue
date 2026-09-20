<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac9x35hjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ac9x35hjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:axis-rotation" /></template>
