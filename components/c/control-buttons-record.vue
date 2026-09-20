<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_d2ngb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k_d2ngb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-record" /></template>
