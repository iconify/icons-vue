<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfz3p5diu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kfz3p5diu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jula-light" /></template>
