<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi_3ok_fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pi_3ok_fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:aspect-ratio-fill" /></template>
