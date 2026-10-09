<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7-lm4bvk.css';
import '../../css/z/zjq3s2ihz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c7-lm4bvk"/><path class="zjq3s2ihz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laundry-basket-20" /></template>
