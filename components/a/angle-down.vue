<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owcch3byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1280};
const content = `<path class="owcch3byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:angle-down" /></template>
