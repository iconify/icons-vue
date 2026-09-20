<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3g0hmf1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3g0hmf1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:happycow" /></template>
