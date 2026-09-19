<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8pfw9bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":112,"height":384};
const content = `<path class="w8pfw9bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:caret-right" /></template>
