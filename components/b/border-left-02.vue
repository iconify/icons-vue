<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umn82f6mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umn82f6mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-left-02" /></template>
