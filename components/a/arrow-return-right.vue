<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcmfr-b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lcmfr-b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-return-right" /></template>
