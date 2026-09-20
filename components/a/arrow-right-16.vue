<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqm-m2bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dqm-m2bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:arrow-right-16" /></template>
