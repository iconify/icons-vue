<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obj86qm_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="obj86qm_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:desktop" /></template>
