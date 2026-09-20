<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m85i73_cc.css';
import '../../css/c/cj59wwj5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m85i73_cc"/><path class="cj59wwj5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buggregator-dark" /></template>
