<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyl1opbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hyl1opbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:briefcase" /></template>
