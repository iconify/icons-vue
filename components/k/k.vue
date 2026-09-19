<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1i_snb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="i1i_snb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:k" /></template>
