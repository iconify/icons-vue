<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3sd78bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c3sd78bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-box-fill-12" /></template>
