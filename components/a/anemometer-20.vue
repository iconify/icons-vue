<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd98t6bsy.css';
import '../../css/n/n6krgwbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nd98t6bsy"/><path class="n6krgwbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:anemometer-20" /></template>
