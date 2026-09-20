<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-smipu6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p-smipu6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-harness" /></template>
