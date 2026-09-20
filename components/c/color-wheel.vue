<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4nvk1g0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x4nvk1g0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:color-wheel" /></template>
