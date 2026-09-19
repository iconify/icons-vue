<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeywum6wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="eeywum6wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:location-arrow" /></template>
