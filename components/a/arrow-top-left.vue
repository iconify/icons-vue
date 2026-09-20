<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ifg30ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p7ifg30ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-top-left" /></template>
