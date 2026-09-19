<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e30u10b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e30u10b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-left-long" /></template>
