<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2bxt1pmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="t2bxt1pmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chevron-right" /></template>
