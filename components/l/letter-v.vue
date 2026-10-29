<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuvvdcctc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuvvdcctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-v" /></template>
