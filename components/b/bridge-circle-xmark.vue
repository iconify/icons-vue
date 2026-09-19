<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot2aw6chb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ot2aw6chb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bridge-circle-xmark" /></template>
