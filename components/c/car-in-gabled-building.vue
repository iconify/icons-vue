<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qemcyt1xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qemcyt1xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-in-gabled-building" /></template>
