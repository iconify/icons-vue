<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zik-cdbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zik-cdbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gateway-inclusive-alt" /></template>
