<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqsj93biv.css';
import '../../css/u/uwl5ht5rg.css';
import '../../css/e/evw_lacsv.css';
import '../../css/p/prfptqbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wqsj93biv"/><path class="uwl5ht5rg"/><path class="evw_lacsv"/><path class="prfptqbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-plus-20-bold" /></template>
