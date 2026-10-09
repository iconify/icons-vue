<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrrfucygy.css';
import '../../css/k/k_lu-3vpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wrrfucygy"/><path class="k_lu-3vpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-half-20-bold" /></template>
