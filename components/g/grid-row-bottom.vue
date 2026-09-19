<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqtl7_d8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqtl7_d8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-row-bottom" /></template>
