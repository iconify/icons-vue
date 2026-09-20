<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1pfkf74d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1pfkf74d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:location-restroom" /></template>
