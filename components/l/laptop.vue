<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqvz_ub4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="zqvz_ub4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:laptop" /></template>
