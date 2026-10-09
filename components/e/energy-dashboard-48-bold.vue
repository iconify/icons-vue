<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5x3dvjat.css';
import '../../css/h/htwye9bzz.css';
import '../../css/b/bo4ks1u_u.css';
import '../../css/c/c9s910gwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l5x3dvjat"/><path class="htwye9bzz"/><path class="bo4ks1u_u"/><path class="c9s910gwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-dashboard-48-bold" /></template>
