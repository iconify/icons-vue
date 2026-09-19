<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhv6agb1d.css';
import '../../css/o/oqcudtb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bhv6agb1d"/><path class="oqcudtb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:asset" /></template>
