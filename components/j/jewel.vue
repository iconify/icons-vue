<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4-2dczzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u4-2dczzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jewel" /></template>
