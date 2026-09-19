<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9u9qcgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tb9u9qcgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-circle-exclamation" /></template>
