<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6forwbcg.css';
import '../../css/k/kh20glbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h6forwbcg"/><path class="kh20glbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-parking-20-bold" /></template>
