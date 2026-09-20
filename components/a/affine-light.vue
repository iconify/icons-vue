<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkfm0bb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hkfm0bb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:affine-light" /></template>
