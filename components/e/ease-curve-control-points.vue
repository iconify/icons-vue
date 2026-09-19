<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6mbt6uzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6mbt6uzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ease-curve-control-points" /></template>
