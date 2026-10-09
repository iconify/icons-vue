<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsbef1xbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vsbef1xbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:countryside-20" /></template>
