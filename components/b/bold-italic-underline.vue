<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rot6e9bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rot6e9bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bold-italic-underline" /></template>
