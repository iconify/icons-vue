<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2w618bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="t2w618bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:indent" /></template>
