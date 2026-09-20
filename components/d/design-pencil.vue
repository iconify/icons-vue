<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi780g99c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zi780g99c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-pencil" /></template>
