<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehc-x0dxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ehc-x0dxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:laptop-file" /></template>
