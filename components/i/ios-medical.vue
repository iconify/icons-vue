<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0kacilch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l0kacilch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-medical" /></template>
