<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysg1y8b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysg1y8b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:magento" /></template>
