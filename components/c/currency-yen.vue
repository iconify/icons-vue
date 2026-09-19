<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toaz7g1ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="toaz7g1ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:currency-yen" /></template>
