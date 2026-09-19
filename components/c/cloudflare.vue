<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-uo_bsyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c-uo_bsyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cloudflare" /></template>
