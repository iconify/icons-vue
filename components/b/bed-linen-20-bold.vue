<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ritmkr3yi.css';
import '../../css/k/kmw8fq5zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ritmkr3yi"/><path class="kmw8fq5zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-linen-20-bold" /></template>
