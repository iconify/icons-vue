<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpwmw9myn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpwmw9myn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:droplet-check" /></template>
