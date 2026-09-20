<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0p15lr5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c0p15lr5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:f" /></template>
