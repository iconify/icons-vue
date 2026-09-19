<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1suj6g3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="v1suj6g3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:long-arrow-down" /></template>
