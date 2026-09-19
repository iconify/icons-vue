<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvq0_2bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvq0_2bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cog" /></template>
