<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5za02bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c5za02bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:font-bold" /></template>
