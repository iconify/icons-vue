<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2m6tab3g.css';
import '../../css/v/v799lmbxv.css';
import '../../css/v/vnf_fxb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f2m6tab3g"/><path class="v799lmbxv"/><path class="vnf_fxb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-tea" /></template>
