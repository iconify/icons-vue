<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkbhw_5_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="hkbhw_5_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:code-commit" /></template>
