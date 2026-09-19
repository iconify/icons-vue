<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6y23s48j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j6y23s48j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:globe-2" /></template>
