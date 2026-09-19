<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_l0y2buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x_l0y2buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bulk-upload" /></template>
