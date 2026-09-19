<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdjls4h-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mdjls4h-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-right-arrow-left" /></template>
