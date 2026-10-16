<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdounc8nc.css';
import '../../css/i/il9s_hbni.css';
import '../../css/p/p5uqo6r1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mdounc8nc"/><path class="il9s_hbni"/><path class="p5uqo6r1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:imbalance-20-bold" /></template>
