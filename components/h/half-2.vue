<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr507ebah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dr507ebah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:half-2" /></template>
