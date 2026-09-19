<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3fx2zb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="t3fx2zb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:8" /></template>
