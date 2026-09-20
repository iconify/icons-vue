<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8uhqvtoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y8uhqvtoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-round-left-solid" /></template>
