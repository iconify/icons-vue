<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4j8ldbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m4j8ldbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:hulf-of-circle-2" /></template>
