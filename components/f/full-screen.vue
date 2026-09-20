<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc9fjabnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zc9fjabnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:full-screen" /></template>
