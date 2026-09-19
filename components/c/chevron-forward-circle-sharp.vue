<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tju_bxjlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tju_bxjlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-forward-circle-sharp" /></template>
