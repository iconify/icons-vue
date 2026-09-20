<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgu72z-ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rgu72z-ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:exclamation-circled" /></template>
