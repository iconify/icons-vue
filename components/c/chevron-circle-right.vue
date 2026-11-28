<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cov3g02at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cov3g02at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chevron-circle-right" /></template>
