<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2bwezb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l2bwezb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:desktop" /></template>
