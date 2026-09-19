<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlmv45btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rlmv45btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-lightning-fill" /></template>
