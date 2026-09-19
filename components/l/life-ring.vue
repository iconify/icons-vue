<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai4n-dk5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ai4n-dk5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:life-ring" /></template>
