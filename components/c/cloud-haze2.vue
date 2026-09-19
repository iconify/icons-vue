<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sptpt9b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sptpt9b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-haze2" /></template>
