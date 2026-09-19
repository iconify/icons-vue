<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb0_8-tpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bb0_8-tpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-sad-tear" /></template>
