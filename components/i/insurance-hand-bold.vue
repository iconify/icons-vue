<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvl2pzwmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvl2pzwmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:insurance-hand-bold" /></template>
