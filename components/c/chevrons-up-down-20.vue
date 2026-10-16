<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot99fcl4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ot99fcl4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-up-down-20" /></template>
