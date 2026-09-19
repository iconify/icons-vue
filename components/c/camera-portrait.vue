<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1u6ybcci.css';
import '../../css/g/gtmkv731h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1u6ybcci"/><path class="gtmkv731h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-portrait" /></template>
