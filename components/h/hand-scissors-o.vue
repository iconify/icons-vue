<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3h5st27g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="k3h5st27g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-scissors-o" /></template>
