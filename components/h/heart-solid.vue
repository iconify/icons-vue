<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no_ee8bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="no_ee8bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:heart-solid" /></template>
