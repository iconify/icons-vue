<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufmo4-xzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1792};
const content = `<path class="ufmo4-xzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:id-badge" /></template>
