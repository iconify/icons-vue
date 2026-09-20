<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzcrxfb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="zzcrxfb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:bag-personal-fill" /></template>
