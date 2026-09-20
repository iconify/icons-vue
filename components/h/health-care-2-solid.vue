<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmrdt7tkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jmrdt7tkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:health-care-2-solid" /></template>
