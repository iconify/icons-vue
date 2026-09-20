<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb0zw44vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gb0zw44vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:key-frame-remix" /></template>
