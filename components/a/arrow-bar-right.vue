<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldz_qwb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ldz_qwb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-bar-right" /></template>
