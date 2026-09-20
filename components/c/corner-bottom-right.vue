<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by0_zkbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="by0_zkbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:corner-bottom-right" /></template>
