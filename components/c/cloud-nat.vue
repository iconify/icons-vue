<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3t-q0_bj.css';
import '../../css/g/gzhvap6lb.css';
import '../../css/r/rrgcllb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3t-q0_bj"/><path class="gzhvap6lb"/><path class="rrgcllb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-nat" /></template>
