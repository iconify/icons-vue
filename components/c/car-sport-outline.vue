<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7_fn5bzo.css';
import '../../css/g/g7v3m3bhf.css';
import '../../css/e/eu_shmbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7_fn5bzo"/><path class="g7v3m3bhf"/><path class="eu_shmbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:car-sport-outline" /></template>
