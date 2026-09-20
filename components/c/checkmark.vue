<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5nchkbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y5nchkbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:checkmark" /></template>
