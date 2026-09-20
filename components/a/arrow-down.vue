<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rolhlfbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="rolhlfbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-down" /></template>
