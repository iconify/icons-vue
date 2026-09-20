<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxgp7eb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zxgp7eb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:location" /></template>
