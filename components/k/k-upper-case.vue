<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csg_4pb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":491,"height":735};
const content = `<path class="csg_4pb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:k-upper-case" /></template>
