<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um721dv4z.css';
import '../../css/w/w96bn_bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um721dv4z"/><path class="w96bn_bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:duck" /></template>
