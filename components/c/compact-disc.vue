<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-9-2ob4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-9-2ob4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:compact-disc" /></template>
