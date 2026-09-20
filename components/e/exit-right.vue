<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1sz4ix2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="z1sz4ix2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:exit-right" /></template>
