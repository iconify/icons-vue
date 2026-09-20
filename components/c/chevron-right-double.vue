<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o82tdabxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="o82tdabxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:chevron-right-double" /></template>
