<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6_snmbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":672};
const content = `<path class="t6_snmbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:logout" /></template>
