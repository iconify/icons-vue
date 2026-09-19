<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfcst0bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfcst0bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:credit-card-01" /></template>
