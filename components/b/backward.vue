<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h66lev3gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h66lev3gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:backward" /></template>
