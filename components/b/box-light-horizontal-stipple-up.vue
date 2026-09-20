<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciwr-ykht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ciwr-ykht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-stipple-up" /></template>
