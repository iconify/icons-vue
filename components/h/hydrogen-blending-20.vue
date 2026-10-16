<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo928wb-m.css';
import '../../css/v/v-mja07rt.css';
import '../../css/k/k494c0bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oo928wb-m"/><path class="v-mja07rt"/><path class="k494c0bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-blending-20" /></template>
