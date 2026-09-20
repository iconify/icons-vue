<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lw7rcr6sy.css';
import '../../css/k/ki4o1yb-o.css';
import '../../css/y/y2fri503s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lw7rcr6sy"/><circle class="ki4o1yb-o"/><circle class="y2fri503s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:cart-shopping" /></template>
