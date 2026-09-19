<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acmmr7ekr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="acmmr7ekr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:bilibili" /></template>
