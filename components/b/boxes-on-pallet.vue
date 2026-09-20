<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipj9a1b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ipj9a1b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:boxes-on-pallet" /></template>
