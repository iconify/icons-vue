<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytw0m4b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ytw0m4b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-from-banknote-in-slot" /></template>
