<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4g3nf-bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4g3nf-bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:mail-line" /></template>
