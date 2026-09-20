<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp5rt_4bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dp5rt_4bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:help" /></template>
