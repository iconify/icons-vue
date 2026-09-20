<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9v4r7bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o9v4r7bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:euro-outline" /></template>
