<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb3ggp-ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="sb3ggp-ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:facebook-f" /></template>
