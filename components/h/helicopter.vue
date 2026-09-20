<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-pfo7vby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="y-pfo7vby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:helicopter" /></template>
