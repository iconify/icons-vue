<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz4xy4xop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tz4xy4xop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bag" /></template>
