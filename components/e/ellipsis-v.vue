<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o16vbibxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":512};
const content = `<path class="o16vbibxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ellipsis-v" /></template>
