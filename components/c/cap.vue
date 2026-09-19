<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf64ielfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf64ielfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cap" /></template>
