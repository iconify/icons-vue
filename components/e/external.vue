<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b48va0b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="b48va0b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:external" /></template>
