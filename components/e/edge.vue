<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1k3llb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1k3llb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:edge" /></template>
