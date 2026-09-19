<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emos5l7br.css';
import '../../css/w/wm69ven1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emos5l7br"/><path class="wm69ven1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-top-alt" /></template>
