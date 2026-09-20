<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-cmdre9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z-cmdre9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:indent-increase" /></template>
