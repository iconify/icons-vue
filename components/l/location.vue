<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3ma3cbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":690,"height":820};
const content = `<path class="k3ma3cbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:location" /></template>
