<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwdjlwbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nwdjlwbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:key-return-noframe-16" /></template>
