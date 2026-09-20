<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6oy1q_yr.css';
import '../../css/u/uai2ftzjf.css';
import '../../css/c/ca5fhmbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6oy1q_yr"/><path class="uai2ftzjf"/><path class="ca5fhmbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:directions-alt" /></template>
