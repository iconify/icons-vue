<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzpx_acik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uzpx_acik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-smile-plus-20-solid" /></template>
