<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1m3h6bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="m1m3h6bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:explosion" /></template>
