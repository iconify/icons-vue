<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-wtosbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":384};
const content = `<path class="b-wtosbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:arrow-out" /></template>
