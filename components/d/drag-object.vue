<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uprmt5bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uprmt5bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:drag-object" /></template>
