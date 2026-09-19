<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwh3lrbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="kwh3lrbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:dot-circle-alt" /></template>
