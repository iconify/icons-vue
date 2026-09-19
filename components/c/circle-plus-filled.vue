<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6_fy5bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e6_fy5bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:circle-plus-filled" /></template>
