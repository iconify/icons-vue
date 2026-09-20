<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n74n5ebcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n74n5ebcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:export" /></template>
