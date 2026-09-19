<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz-w_gbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kz-w_gbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:flag" /></template>
