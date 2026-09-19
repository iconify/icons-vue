<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz6fzlwom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tz6fzlwom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-point-down" /></template>
