<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqjz3mnhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqjz3mnhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:language-filled" /></template>
