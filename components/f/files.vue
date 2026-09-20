<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmb9pi-5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dmb9pi-5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:files" /></template>
