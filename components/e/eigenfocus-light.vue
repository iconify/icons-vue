<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1th6cc6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1th6cc6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eigenfocus-light" /></template>
