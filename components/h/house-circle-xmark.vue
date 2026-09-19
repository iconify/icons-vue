<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e75fnac6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e75fnac6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-circle-xmark" /></template>
