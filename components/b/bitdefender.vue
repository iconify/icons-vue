<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll1cpmbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ll1cpmbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bitdefender" /></template>
