<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwqdcgbku.css';
import '../../css/o/oow25ab3t.css';
import '../../css/p/pc1ke3bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nwqdcgbku"/><path class="oow25ab3t"/><path class="pc1ke3bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bot-20-bold" /></template>
