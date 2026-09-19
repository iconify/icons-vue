<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym7s1o7nd.css';
import '../../css/c/cgzpch7-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ym7s1o7nd"/><path class="cgzpch7-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bicycle" /></template>
