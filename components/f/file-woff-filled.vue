<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lowya3gvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lowya3gvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-woff-filled" /></template>
