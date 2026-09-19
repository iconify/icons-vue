<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag_fw_b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ag_fw_b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-up-right-circle" /></template>
