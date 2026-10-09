<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg8tnbcvl.css';
import '../../css/s/sx-04bc4i.css';
import '../../css/r/rwowwm9cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xg8tnbcvl"/><path class="sx-04bc4i"/><path class="rwowwm9cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cogs-20-bold" /></template>
