<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4vmcpb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x4vmcpb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:heartbreak-fill" /></template>
