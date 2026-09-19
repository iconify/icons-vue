<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyu3_qfzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pyu3_qfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bag-check-fill" /></template>
