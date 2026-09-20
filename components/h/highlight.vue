<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj5drf1ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xj5drf1ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:highlight" /></template>
