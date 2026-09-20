<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olzr79b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="olzr79b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:close" /></template>
