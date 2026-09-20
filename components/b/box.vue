<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wde4g70nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wde4g70nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:box" /></template>
