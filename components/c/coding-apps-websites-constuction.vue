<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md0h0dbps.css';
import '../../css/l/loqdhccef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="md0h0dbps"/><path class="loqdhccef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:coding-apps-websites-constuction" /></template>
