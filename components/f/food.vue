<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4ktayvon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r4ktayvon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:food" /></template>
