<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it4d2uboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="it4d2uboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-play" /></template>
