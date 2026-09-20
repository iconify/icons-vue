<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3hk2vf-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z3hk2vf-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-down" /></template>
