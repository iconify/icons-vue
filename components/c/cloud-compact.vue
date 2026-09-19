<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtftanbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xtftanbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:cloud-compact" /></template>
