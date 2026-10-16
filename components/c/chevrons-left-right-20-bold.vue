<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwob-oc1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kwob-oc1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-left-right-20-bold" /></template>
