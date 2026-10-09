<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itlombx0k.css';
import '../../css/c/cbxvuvbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itlombx0k"/><path class="cbxvuvbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-sankey-20" /></template>
