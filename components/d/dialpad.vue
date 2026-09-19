<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkepnv0au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":480};
const content = `<path class="qkepnv0au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:dialpad" /></template>
