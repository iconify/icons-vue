<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg690wp1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="qg690wp1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:bell" /></template>
