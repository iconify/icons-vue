<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl7u8lp9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl7u8lp9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-autofit-down" /></template>
