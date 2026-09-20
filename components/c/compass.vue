<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr1bk8ial.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nr1bk8ial"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:compass" /></template>
