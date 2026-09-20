<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgjbclbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qgjbclbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:build-16" /></template>
