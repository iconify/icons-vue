<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aww87p9pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="aww87p9pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:asterisk" /></template>
