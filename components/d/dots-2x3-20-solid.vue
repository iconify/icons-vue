<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlsl8d1ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qlsl8d1ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3-20-solid" /></template>
