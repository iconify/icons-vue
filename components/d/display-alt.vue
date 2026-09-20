<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9cdcizyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h9cdcizyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:display-alt" /></template>
