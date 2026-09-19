<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_ixp2b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o_ixp2b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:image-rotate-left" /></template>
