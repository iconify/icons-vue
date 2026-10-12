<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp3lwibtz.css';
import '../../css/m/mdwpa6sgu.css';
import '../../css/u/udgxuob1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lp3lwibtz"/><path class="mdwpa6sgu"/><path class="udgxuob1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:feather-48-bold" /></template>
