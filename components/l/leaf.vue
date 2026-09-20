<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz8h51bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zz8h51bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:leaf" /></template>
