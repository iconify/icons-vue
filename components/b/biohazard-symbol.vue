<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogklqrmiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ogklqrmiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:biohazard-symbol" /></template>
