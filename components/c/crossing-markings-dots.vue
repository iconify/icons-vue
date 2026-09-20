<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t39xeubio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t39xeubio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:crossing-markings-dots" /></template>
