<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rijvy-f8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rijvy-f8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:font-family" /></template>
