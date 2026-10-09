<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k98tn-izd.css';
import '../../css/m/mjb6-8gcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k98tn-izd"/><path class="mjb6-8gcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:generator-20-bold" /></template>
