<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxvf2cbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mxvf2cbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:arrow-down-outline" /></template>
