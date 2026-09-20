<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8p3x7bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8p3x7bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:expand" /></template>
