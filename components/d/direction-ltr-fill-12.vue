<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cytyfkvmo.css';
import '../../css/y/y2gcv4obb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cytyfkvmo"/><path class="y2gcv4obb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:direction-ltr-fill-12" /></template>
