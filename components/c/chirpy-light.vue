<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojcv45blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojcv45blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chirpy-light" /></template>
