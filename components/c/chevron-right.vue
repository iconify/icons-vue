<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah7_xrbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ah7_xrbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:chevron-right" /></template>
