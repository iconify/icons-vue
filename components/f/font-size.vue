<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv2w0mb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pv2w0mb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:font-size" /></template>
