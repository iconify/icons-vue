<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx9uqla7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qx9uqla7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:boot" /></template>
