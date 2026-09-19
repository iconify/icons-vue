<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2_ijpk0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2_ijpk0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clapperboard" /></template>
