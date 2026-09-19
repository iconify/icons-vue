<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr9ytkb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="hr9ytkb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:caret-down" /></template>
