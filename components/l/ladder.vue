<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz4tvtbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pz4tvtbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:ladder" /></template>
