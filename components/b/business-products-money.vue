<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ns15bcg.css';
import '../../css/l/lgj5z1bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n9ns15bcg"/><path class="lgj5z1bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-money" /></template>
