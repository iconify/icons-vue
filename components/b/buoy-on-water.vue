<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nef45ubzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nef45ubzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:buoy-on-water" /></template>
