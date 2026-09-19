<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj14-pijc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wj14-pijc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-bar-square-fill" /></template>
