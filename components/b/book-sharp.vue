<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0snn2bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r0snn2bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:book-sharp" /></template>
