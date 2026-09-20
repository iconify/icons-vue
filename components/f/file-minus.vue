<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc91mi2ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cc91mi2ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:file-minus" /></template>
