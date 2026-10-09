<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-nqb5bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c-nqb5bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-loss-20-bold" /></template>
