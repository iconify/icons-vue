<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-82anbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-82anbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hockey-puck" /></template>
