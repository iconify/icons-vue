<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-7hzubuy.css';
import '../../css/m/m2p7gebqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j-7hzubuy"/><path class="m2p7gebqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lattice-dish-antenna-left-dish-antenna-right" /></template>
