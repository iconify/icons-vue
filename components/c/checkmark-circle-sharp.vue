<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka4u2_gho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ka4u2_gho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:checkmark-circle-sharp" /></template>
