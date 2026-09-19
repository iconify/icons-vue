<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w__hynbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":440};
const content = `<path class="w__hynbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:dribbble" /></template>
