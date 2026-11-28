<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsqui2via.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsqui2via"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:diamond" /></template>
