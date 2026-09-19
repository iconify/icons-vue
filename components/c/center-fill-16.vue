<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqrqcmb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nqrqcmb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:center-fill-16" /></template>
