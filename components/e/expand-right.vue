<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-1cqfbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-1cqfbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:expand-right" /></template>
