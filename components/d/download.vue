<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r97-9822y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r97-9822y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:download" /></template>
