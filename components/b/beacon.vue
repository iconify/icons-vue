<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgk_kmbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zgk_kmbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:beacon" /></template>
