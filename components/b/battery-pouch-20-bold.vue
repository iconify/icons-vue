<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw-oesbrl.css';
import '../../css/n/nuvmf9bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uw-oesbrl"/><path class="nuvmf9bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pouch-20-bold" /></template>
