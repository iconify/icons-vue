<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1beksb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m1beksb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:artboard-solid" /></template>
