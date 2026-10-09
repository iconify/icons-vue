<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgo-bn5bm.css';
import '../../css/d/dsjehubcj.css';
import '../../css/j/jyfi0eawb.css';
import '../../css/w/wii29dbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pgo-bn5bm"/><path class="dsjehubcj"/><path class="jyfi0eawb"/><path class="wii29dbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-plus-48-bold" /></template>
