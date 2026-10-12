<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn1v_kase.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mn1v_kase"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:inbox-stroke-20" /></template>
