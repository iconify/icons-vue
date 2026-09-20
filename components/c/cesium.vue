<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr32_5ygq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr32_5ygq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cesium" /></template>
