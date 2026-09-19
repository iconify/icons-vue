<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_wb409zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u_wb409zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:fire-small" /></template>
