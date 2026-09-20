<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd87fv_an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rd87fv_an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bollard-row" /></template>
