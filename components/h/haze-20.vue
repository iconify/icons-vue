<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_hv1kb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r_hv1kb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:haze-20" /></template>
