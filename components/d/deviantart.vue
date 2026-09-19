<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqydd_blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="pqydd_blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:deviantart" /></template>
