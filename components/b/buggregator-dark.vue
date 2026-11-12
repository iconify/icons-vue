<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbst8fbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kbst8fbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buggregator-dark" /></template>
