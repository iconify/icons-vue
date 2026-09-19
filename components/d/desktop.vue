<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnb5ity-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qnb5ity-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:desktop" /></template>
