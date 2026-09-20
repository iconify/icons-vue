<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f38hztbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f38hztbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horizontal-storage-tank-on-supports" /></template>
