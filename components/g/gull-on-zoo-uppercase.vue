<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldrvy3bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ldrvy3bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gull-on-zoo-uppercase" /></template>
