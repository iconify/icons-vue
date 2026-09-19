<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5-g-c5hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5-g-c5hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-right-box-outline" /></template>
