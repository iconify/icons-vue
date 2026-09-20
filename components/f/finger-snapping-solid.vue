<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz727r4ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tz727r4ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:finger-snapping-solid" /></template>
