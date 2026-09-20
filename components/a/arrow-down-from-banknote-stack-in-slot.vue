<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz9ab3bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wz9ab3bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-from-banknote-stack-in-slot" /></template>
