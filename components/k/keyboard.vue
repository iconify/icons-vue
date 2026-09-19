<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc-b0jlzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="tc-b0jlzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:keyboard" /></template>
