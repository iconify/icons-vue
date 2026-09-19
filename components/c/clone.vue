<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugv1xtbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugv1xtbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clone" /></template>
