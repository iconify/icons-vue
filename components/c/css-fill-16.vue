<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2cni_bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v2cni_bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:css-fill-16" /></template>
