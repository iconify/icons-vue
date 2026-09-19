<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/sk4_933ij.css';
import '../../css/l/l230f71as.css';
import '../../css/o/opswthbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="sk4_933ij"/><path class="l230f71as"/><path class="opswthbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:gift-outline" /></template>
