<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smmymf_ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":392};
const content = `<path class="smmymf_ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-color-reset" /></template>
