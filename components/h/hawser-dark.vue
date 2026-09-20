<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pphwdzbsq.css';
import '../../css/j/jxqbrew3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pphwdzbsq"/><path class="jxqbrew3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hawser-dark" /></template>
