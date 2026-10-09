<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7dkqbcdb.css';
import '../../css/e/enzpns2dp.css';
import '../../css/o/o3au9s7tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7dkqbcdb"/><path class="enzpns2dp"/><path class="o3au9s7tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cabin-20" /></template>
