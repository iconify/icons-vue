<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esxy8zbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="esxy8zbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:globe-asia-solid" /></template>
