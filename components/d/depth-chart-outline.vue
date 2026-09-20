<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui3ma-bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ui3ma-bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:depth-chart-outline" /></template>
