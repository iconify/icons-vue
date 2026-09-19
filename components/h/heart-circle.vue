<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3roe6gyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="l3roe6gyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:heart-circle" /></template>
