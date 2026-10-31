<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd89ibzna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kd89ibzna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-gabled-building" /></template>
