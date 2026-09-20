<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t522e0tcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t522e0tcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:font-italic" /></template>
