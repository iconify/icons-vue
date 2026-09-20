<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwq1ytbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="gwq1ytbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:electrician" /></template>
