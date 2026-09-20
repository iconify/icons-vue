<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oud75tbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oud75tbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:infuse-one-outline" /></template>
