<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z79fcum9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z79fcum9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:iowa" /></template>
