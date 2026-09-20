<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jecvu-cad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jecvu-cad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:f" /></template>
