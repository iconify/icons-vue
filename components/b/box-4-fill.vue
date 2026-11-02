<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eib-fmbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eib-fmbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:box-4-fill" /></template>
