<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ri_k4mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c1ri_k4mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aria2-light" /></template>
