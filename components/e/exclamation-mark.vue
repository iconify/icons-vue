<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4_s0eafu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m4_s0eafu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:exclamation-mark" /></template>
