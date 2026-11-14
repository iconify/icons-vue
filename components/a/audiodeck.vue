<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puwug5bgg.css';
import '../../css/h/ht9cs5buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="puwug5bgg"/><path class="ht9cs5buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audiodeck" /></template>
