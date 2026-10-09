<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnes2-b0p.css';
import '../../css/w/wofyv04is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hnes2-b0p"/><path class="wofyv04is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cactus-20" /></template>
