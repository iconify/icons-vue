<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdptq_7jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="gdptq_7jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:democrat" /></template>
