<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0a_4572c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n0a_4572c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:diamond" /></template>
