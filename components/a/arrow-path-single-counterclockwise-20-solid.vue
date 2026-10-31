<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k16cutbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k16cutbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-counterclockwise-20-solid" /></template>
