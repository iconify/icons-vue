<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2yto2b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m2yto2b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:heart-dislike-sharp" /></template>
