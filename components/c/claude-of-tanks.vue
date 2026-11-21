<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omuyjcckl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":9956,"height":700,"left":55,"top":142};
const content = `<path class="omuyjcckl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:claude-of-tanks" /></template>
