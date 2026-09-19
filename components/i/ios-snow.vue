<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2o7--wpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2o7--wpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-snow" /></template>
