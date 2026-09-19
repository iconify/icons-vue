<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sciuggb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="sciuggb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cat" /></template>
