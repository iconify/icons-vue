<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so4b4tb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="so4b4tb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:component-none" /></template>
