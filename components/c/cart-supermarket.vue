<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvtgyfbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":496};
const content = `<path class="dvtgyfbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:cart-supermarket" /></template>
