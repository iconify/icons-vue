<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nors1t8an.css';
import '../../css/m/mr67hub_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nors1t8an"/><path class="mr67hub_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-plant-20-bold" /></template>
