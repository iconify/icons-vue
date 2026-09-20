<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp6emhbkc.css';
import '../../css/t/ti4c50bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tp6emhbkc"/><path class="ti4c50bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ambulance" /></template>
