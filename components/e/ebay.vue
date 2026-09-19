<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouz92dbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouz92dbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ebay" /></template>
