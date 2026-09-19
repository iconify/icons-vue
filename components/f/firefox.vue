<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqalf3b1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pqalf3b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:firefox" /></template>
