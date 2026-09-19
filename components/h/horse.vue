<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbsk2ebxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hbsk2ebxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:horse" /></template>
